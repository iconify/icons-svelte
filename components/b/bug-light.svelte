<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq8xb2ljf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qq8xb2ljf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:bug-light" {...props}></Icon>

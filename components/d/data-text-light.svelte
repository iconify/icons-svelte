<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxzum9b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxzum9b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-text-light" {...props}></Icon>

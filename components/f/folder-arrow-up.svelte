<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_fj7sb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_fj7sb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-arrow-up" {...props}></Icon>

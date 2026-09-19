<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uri5h4b8u.css';
import '../../css/c/ct5b1-o3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="uri5h4b8u"/><path class="ct5b1-o3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:action-chains" {...props}></Icon>

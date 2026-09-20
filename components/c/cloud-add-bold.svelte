<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8lu4ibzi.css';
import '../../css/a/asyh4bbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8lu4ibzi"/><path class="asyh4bbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cloud-add-bold" {...props}></Icon>

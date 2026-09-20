<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmmlnjhhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmmlnjhhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:remove-square-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-ucjcbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o-ucjcbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:cloud-nut-hex" {...props}></Icon>

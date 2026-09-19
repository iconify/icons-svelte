<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfwczgxqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vfwczgxqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:person-worker" {...props}></Icon>

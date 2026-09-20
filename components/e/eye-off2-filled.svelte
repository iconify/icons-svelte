<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht4j2lblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ht4j2lblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:eye-off2-filled" {...props}></Icon>

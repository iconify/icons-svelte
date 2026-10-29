<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqh_f-kog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqh_f-kog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-commit-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d628jkbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d628jkbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bracket-curly" {...props}></Icon>

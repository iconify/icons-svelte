<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tddmvachw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tddmvachw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-forward" {...props}></Icon>

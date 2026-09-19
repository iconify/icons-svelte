<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3wp4wbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3wp4wbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:health-alt-24px" {...props}></Icon>

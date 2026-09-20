<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c187v82dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c187v82dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-24" {...props}></Icon>

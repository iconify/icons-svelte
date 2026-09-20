<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfemr9pud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfemr9pud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ease-out" {...props}></Icon>

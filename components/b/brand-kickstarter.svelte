<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcivtz0ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcivtz0ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-kickstarter" {...props}></Icon>

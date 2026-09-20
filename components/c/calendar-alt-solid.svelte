<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg8faqbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg8faqbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:calendar-alt-solid" {...props}></Icon>

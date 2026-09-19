<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbl60data.css';
import '../../css/t/ty9-8db6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbl60data"/><path class="ty9-8db6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:printer" {...props}></Icon>

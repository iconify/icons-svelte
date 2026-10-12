<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g647b6wru.css';
import '../../css/a/abpmulcbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g647b6wru"/><path class="abpmulcbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-arrow-down-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clbb1mjyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="clbb1mjyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:down" {...props}></Icon>

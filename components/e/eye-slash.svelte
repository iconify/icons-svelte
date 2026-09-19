<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3peti11w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q3peti11w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:eye-slash" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8ib-cu8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8ib-cu8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-asterisk" {...props}></Icon>

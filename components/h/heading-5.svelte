<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umrq6t13x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="umrq6t13x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:heading-5" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi65es6xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi65es6xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:maximize" {...props}></Icon>

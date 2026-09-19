<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng-12ub9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ng-12ub9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:build-tool" {...props}></Icon>

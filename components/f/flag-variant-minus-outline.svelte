<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adt168bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adt168bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-variant-minus-outline" {...props}></Icon>

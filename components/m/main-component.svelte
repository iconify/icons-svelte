<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8oj_3bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8oj_3bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:main-component" {...props}></Icon>

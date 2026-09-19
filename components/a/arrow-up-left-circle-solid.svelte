<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef983wb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ef983wb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-up-left-circle-solid" {...props}></Icon>

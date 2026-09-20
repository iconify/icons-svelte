<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c43qe1bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c43qe1bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dice-four-solid" {...props}></Icon>

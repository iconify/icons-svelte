<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sznxx_but.css';
import '../../css/d/dduzo9-ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sznxx_but"/><path class="dduzo9-ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:credit-card-1" {...props}></Icon>

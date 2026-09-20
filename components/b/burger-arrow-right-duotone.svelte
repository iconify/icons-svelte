<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uibqwacqf.css';
import '../../css/s/sz5bu0b9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uibqwacqf"/><path class="sz5bu0b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger-arrow-right-duotone" {...props}></Icon>

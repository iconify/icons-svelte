<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukh3251yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukh3251yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:building-alt-2-line" {...props}></Icon>

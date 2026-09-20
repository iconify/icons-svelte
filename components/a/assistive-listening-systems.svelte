<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du-lkubnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du-lkubnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:assistive-listening-systems" {...props}></Icon>

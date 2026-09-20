<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wflyv4bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wflyv4bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-one-or-many-to-only-one" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c818x0b4f.css';
import '../../css/v/vrte_9f8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="c818x0b4f"/><path class="vrte_9f8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:lock-fill" {...props}></Icon>

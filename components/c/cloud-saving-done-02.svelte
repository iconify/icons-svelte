<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peld2mb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peld2mb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-saving-done-02" {...props}></Icon>

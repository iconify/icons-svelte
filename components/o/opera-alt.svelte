<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwh6ukbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwh6ukbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:opera-alt" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdk6zdbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdk6zdbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:department-store-filled" {...props}></Icon>

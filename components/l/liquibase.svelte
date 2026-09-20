<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzqw7kbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzqw7kbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:liquibase" {...props}></Icon>

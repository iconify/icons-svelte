<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap9k2cboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap9k2cboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:person-chalkboard-outline" {...props}></Icon>

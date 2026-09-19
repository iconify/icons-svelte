<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb7gpob6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qb7gpob6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:input-latin-capital-letters" {...props}></Icon>

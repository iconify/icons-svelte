<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awm81q2hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="awm81q2hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:liquibase" {...props}></Icon>

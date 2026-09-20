<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npk_kkbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="npk_kkbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bitbucket-solid" {...props}></Icon>

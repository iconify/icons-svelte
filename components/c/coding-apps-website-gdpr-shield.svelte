<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_l7b9b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_l7b9b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-gdpr-shield" {...props}></Icon>

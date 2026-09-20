<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw-y_2o8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cw-y_2o8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:beyondcorp-enterprise-logo-block" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecpj_td6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ecpj_td6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bitbucket-logo-solid" {...props}></Icon>

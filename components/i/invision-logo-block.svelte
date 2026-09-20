<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/petscgbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="petscgbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:invision-logo-block" {...props}></Icon>

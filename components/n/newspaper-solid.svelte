<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqom69dqx.css';
import '../../css/v/vonci7bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqom69dqx"/><path class="vonci7bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:newspaper-solid" {...props}></Icon>

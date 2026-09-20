<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5-kd2jkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:katana" {...props}></Icon>
<style>
:global(.e5-kd2jkh) {
  fill: var(--svg-color--f6ff0d, #f6ff0d);
  d: path("M10.64 9.272L14.236 3h3.595l-2.696 8.978H12.46l7.189 3.59L16.033 21l-5.392-6.313v4.473H4.35l2.156-7.182H4.351L7.046 3h3.595z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idl8_ab9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pulpit" {...props}></Icon>
<style>
:global(.idl8_ab9i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.08 7.35l13.84-3.7q.58-.15.58.45v5.3q0 .6-.6.6H5.1q-.6 0-.6-.6V8.1q0-.6.58-.75M12 10v11.25m-4.5 0h9");
}

</style>
